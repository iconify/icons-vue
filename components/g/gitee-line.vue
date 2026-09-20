<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew1-g2bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew1-g2bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gitee-line" /></template>
