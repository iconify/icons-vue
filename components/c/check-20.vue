<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3kixubtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p3kixubtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-20" /></template>
