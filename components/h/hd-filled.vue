<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h717r1b5y.css';
import '../../css/q/qvcljuewd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h717r1b5y"/><path class="qvcljuewd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hd-filled" /></template>
