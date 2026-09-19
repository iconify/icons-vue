<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d27yqc0ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d27yqc0ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:flash-auto" /></template>
