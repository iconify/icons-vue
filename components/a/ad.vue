<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvey1b9tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cvey1b9tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ad" /></template>
