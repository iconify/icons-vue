<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxwc_zbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lxwc_zbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:add-large" /></template>
