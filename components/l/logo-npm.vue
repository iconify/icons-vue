<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar049kb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ar049kb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-npm" /></template>
