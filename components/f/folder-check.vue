<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-7s0mshg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z-7s0mshg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:folder-check" /></template>
