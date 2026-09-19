<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d27bhtbqq.css';
import '../../css/v/v0283z18f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d27bhtbqq"/><path class="v0283z18f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:enter-outline" /></template>
