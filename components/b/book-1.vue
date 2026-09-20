<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v53dv9otu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v53dv9otu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:book-1" /></template>
