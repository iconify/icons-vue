<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3me-4caq.css';
import '../../css/r/rr-f5tb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c3me-4caq"/><path class="rr-f5tb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-star-20" /></template>
