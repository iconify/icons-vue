<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfdw6bbqs.css';
import '../../css/k/kpsjv5nug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nfdw6bbqs"/><path class="kpsjv5nug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:garden-bench-20" /></template>
