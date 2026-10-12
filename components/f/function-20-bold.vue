<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx4xreset.css';
import '../../css/h/hyx6j7bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qx4xreset"/><path class="hyx6j7bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:function-20-bold" /></template>
