<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh0s2-9xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kh0s2-9xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:close" /></template>
