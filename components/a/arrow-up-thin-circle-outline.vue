<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxfhco1bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxfhco1bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-thin-circle-outline" /></template>
