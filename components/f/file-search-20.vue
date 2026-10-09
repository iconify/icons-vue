<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zevx3_zmp.css';
import '../../css/a/anynp2b3h.css';
import '../../css/c/cn7q8feaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zevx3_zmp"/><path class="anynp2b3h"/><path class="cn7q8feaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-search-20" /></template>
