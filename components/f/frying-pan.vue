<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbh0m6b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbh0m6b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:frying-pan" /></template>
