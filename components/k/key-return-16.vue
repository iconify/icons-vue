<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys6txvbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ys6txvbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:key-return-16" /></template>
