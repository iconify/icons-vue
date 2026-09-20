<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz6lu0z5m.css';
import '../../css/l/lfanpcblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="zz6lu0z5m"/><path class="lfanpcblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:loading-3-line" /></template>
