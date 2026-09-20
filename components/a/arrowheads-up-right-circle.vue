<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6-k0_bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f6-k0_bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-up-right-circle" /></template>
