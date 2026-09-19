<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbmwvhb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hbmwvhb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:currency-euro" /></template>
