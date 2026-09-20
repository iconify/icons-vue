<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itwh__bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="itwh__bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:battery-quarter-solid" /></template>
