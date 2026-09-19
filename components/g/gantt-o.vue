<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbd9-edzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1600};
const content = `<path class="bbd9-edzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:gantt-o" /></template>
