<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewjnt-fjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewjnt-fjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-armn-to" /></template>
