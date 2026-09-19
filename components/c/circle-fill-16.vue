<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp9lib0uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<circle class="rp9lib0uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-fill-16" /></template>
