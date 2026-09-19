<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1vjxgbrn.css';
import '../../css/j/j2qx5-bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s1vjxgbrn"/><path class="j2qx5-bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:alarm-clock" /></template>
