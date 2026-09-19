<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr2_dksop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr2_dksop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:kitchen" /></template>
