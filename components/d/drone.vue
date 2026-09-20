<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olxuds8oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":230,"height":230};
const content = `<path class="olxuds8oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:drone" /></template>
