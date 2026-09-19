<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qre1wn1gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qre1wn1gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-appearance" /></template>
