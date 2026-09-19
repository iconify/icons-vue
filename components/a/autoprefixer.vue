<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onl5fdbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="onl5fdbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:autoprefixer" /></template>
