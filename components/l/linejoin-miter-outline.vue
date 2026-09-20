<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph0w2_b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ph0w2_b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linejoin-miter-outline" /></template>
