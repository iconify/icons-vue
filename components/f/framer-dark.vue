<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmhsw6grh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="lmhsw6grh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:framer-dark" /></template>
