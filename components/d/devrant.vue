<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvcvb6bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qvcvb6bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:devrant" /></template>
