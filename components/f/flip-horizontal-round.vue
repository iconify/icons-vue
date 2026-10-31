<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtevnmbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtevnmbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal-round" /></template>
