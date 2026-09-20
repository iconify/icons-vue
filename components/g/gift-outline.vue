<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmb6sebto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fmb6sebto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:gift-outline" /></template>
