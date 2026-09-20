<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m98lz0v9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m98lz0v9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:carrot" /></template>
