<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6182vc9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="c6182vc9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-s-fill" /></template>
