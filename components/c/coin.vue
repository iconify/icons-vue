<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4go9bboz.css';
import '../../css/y/y1vck7bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o4go9bboz"/><path class="y1vck7bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:coin" /></template>
