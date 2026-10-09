<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1w9q6o5b.css';
import '../../css/d/d9t-opb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c1w9q6o5b"/><path class="d9t-opb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-20-bold" /></template>
