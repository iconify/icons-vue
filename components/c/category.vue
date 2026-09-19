<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgn19vb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":551,"height":717};
const content = `<path class="rgn19vb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:category" /></template>
