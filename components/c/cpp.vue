<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz-b1_byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="sz-b1_byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cpp" /></template>
