<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbqlp8bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbqlp8bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:cablecar" /></template>
