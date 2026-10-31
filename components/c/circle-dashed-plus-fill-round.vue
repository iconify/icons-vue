<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz8e6p2tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz8e6p2tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-plus-fill-round" /></template>
