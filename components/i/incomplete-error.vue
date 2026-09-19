<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd6_5ub6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jd6_5ub6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:incomplete-error" /></template>
