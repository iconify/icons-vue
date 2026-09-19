<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag11jn0th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ag11jn0th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:battery-error" /></template>
