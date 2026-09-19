<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lona2hrqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lona2hrqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:format-aside" /></template>
