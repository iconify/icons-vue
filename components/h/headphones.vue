<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/patlzsgzl.css';
import '../../css/d/dvh2bwuis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="patlzsgzl"/><path class="dvh2bwuis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:headphones" /></template>
