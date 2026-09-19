<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onb4l0cqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="onb4l0cqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-fog2" /></template>
