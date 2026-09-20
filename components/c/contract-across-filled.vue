<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3cfpd7tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3cfpd7tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:contract-across-filled" /></template>
