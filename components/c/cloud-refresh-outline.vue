<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu736w-hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu736w-hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-refresh-outline" /></template>
