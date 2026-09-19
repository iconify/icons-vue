<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc4r43bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kc4r43bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:italic-stroke-12" /></template>
