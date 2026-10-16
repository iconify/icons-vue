<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezhonm73e.css';
import '../../css/k/k2af-4bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ezhonm73e"/><path class="k2af-4bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-code-20" /></template>
