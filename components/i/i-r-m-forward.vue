<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt4e19b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gt4e19b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:i-r-m-forward" /></template>
