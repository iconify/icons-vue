<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd35uf49z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rd35uf49z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-skip-back" /></template>
