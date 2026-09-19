<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1b98fbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f1b98fbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:coffee" /></template>
