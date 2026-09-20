<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6mqt5ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oj6mqt5ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:losange-16" /></template>
