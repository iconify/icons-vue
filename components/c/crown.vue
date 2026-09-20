<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0s_u7b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u0s_u7b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:crown" /></template>
