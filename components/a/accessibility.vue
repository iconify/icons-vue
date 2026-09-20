<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyqka1bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uyqka1bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:accessibility" /></template>
