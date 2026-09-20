<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwc05acsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwc05acsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-height-fill" /></template>
