<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdguspb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cdguspb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:clipboard" /></template>
