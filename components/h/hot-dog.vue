<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugbis8cfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ugbis8cfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hot-dog" /></template>
