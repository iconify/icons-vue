<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzcd-gs6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="nzcd-gs6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:headphones" /></template>
