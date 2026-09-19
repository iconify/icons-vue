<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5f5q0zdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k5f5q0zdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:burger" /></template>
