<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tchbe2b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tchbe2b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:facebook" /></template>
