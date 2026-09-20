<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bznz2_2wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960,"top":-960};
const content = `<path class="bznz2_2wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:json" /></template>
