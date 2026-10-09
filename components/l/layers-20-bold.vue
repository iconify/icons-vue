<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5yiolbrq.css';
import '../../css/q/qsgv5bbpc.css';
import '../../css/z/zf9x55bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e5yiolbrq"/><path class="qsgv5bbpc"/><path class="zf9x55bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:layers-20-bold" /></template>
