<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik8ucng6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ik8ucng6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-up-left-circle" /></template>
