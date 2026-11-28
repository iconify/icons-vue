<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyx-p81np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uyx-p81np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clock-plus-bold" /></template>
