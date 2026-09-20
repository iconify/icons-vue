<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmxkbubax.css';
import '../../css/q/qrl3wtblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmxkbubax"/><path class="qrl3wtblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:link" /></template>
