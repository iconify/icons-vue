<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfj5y64ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gfj5y64ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:emissions-management" /></template>
