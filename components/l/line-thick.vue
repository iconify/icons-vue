<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dodfwrerp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dodfwrerp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:line-thick" /></template>
