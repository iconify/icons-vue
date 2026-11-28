<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keov08rnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keov08rnv primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-right-through-line-duotone" /></template>
