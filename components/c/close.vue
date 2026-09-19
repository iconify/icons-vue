<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9j3-mbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b9j3-mbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:close" /></template>
