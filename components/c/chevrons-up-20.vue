<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8i01qb4b.css';
import '../../css/z/z5m9jtb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n8i01qb4b"/><path class="z5m9jtb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-up-20" /></template>
