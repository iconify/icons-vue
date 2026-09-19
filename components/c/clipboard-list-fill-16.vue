<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtt6g2roz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qtt6g2roz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-list-fill-16" /></template>
