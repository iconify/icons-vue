<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgzte6aqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kgzte6aqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:code" /></template>
