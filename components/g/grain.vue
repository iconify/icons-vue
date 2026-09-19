<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3k5vebsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="u3k5vebsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:grain" /></template>
