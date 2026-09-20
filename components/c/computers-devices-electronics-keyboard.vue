<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj39dlnoc.css';
import '../../css/w/wfdwuhjle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bj39dlnoc"/><path class="wfdwuhjle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-keyboard" /></template>
