<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf5gvfb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tf5gvfb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:book-reference" /></template>
