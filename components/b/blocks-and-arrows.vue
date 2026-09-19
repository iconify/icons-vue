<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvv1ubwib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvv1ubwib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:blocks-and-arrows" /></template>
