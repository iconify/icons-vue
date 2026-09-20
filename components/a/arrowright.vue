<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox032cbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ox032cbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:arrowright" /></template>
