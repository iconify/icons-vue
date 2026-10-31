<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvs2kr1fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvs2kr1fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-round" /></template>
