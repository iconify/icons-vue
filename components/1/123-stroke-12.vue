<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwr21lb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lwr21lb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:123-stroke-12" /></template>
