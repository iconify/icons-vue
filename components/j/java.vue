<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp8g4kbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zp8g4kbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:java" /></template>
