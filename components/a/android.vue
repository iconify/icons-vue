<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccxukbbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ccxukbbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:android" /></template>
