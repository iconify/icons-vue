<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqu884bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqu884bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:euro-gloss" /></template>
