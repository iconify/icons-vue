<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipn51glyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ipn51glyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:grid-circle" /></template>
