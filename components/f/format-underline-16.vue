<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1rj3bivm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n1rj3bivm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:format-underline-16" /></template>
