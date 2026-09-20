<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukyr80b4m.css';
import '../../css/z/zbs1n8-tz.css';
import '../../css/y/yynvv2qce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukyr80b4m"/><path class="zbs1n8-tz"/><path class="yynvv2qce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cassette-tape" /></template>
