<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0c1uhphr.css';
import '../../css/k/kx2q3nbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d0c1uhphr"/><path class="kx2q3nbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:link" /></template>
