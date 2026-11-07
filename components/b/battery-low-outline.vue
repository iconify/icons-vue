<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnqh4sixl.css';
import '../../css/n/n2noceb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnqh4sixl"/><path clip-rule="evenodd" class="n2noceb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-low-outline" /></template>
