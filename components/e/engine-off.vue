<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agfqxb0el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agfqxb0el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:engine-off" /></template>
