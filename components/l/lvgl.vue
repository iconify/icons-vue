<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axmd_h3dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axmd_h3dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lvgl" /></template>
