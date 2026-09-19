<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsjtpacxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xsjtpacxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-bottom-right-center-8" /></template>
