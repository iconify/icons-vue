<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnm2yubav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nnm2yubav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:history-fill-16" /></template>
