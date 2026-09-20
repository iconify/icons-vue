<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1ucyg85g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f1ucyg85g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-right-circle" /></template>
