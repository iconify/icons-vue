<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-lmivhtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-lmivhtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:indent-increase-stroke-16" /></template>
