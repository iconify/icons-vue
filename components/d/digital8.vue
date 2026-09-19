<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5xl8acvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a5xl8acvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital8" /></template>
