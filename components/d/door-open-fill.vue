<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8d2m-gls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f8d2m-gls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:door-open-fill" /></template>
