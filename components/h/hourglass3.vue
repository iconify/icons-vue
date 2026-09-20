<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfpvy8bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bfpvy8bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass3" /></template>
