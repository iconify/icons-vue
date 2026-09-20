<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfy-dishp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yfy-dishp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:cross" /></template>
