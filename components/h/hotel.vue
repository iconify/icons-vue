<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpp4vf5pi.css';
import '../../css/q/qhx66epws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zpp4vf5pi"/><path class="qhx66epws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hotel" /></template>
