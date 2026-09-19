<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0e3n1ckb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="q0e3n1ckb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-forward" /></template>
