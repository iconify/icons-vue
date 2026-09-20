<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozs9embjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ozs9embjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:die-face-with-five-pips" /></template>
