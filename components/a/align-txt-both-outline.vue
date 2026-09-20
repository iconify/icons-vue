<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0l9zdeaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y0l9zdeaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:align-txt-both-outline" /></template>
