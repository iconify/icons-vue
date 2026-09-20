<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmhakjb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qmhakjb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-empty-1" /></template>
