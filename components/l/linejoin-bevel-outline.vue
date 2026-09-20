<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftd8t6bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ftd8t6bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linejoin-bevel-outline" /></template>
