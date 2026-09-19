<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obive6x0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obive6x0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:line-squiggle" /></template>
