<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvrt6vnvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvrt6vnvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:bench-ts" /></template>
