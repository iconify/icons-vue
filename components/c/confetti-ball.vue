<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn_6w-26x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pn_6w-26x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:confetti-ball" /></template>
