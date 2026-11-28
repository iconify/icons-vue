<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxgn_9bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fxgn_9bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:envelope-check-thin" /></template>
