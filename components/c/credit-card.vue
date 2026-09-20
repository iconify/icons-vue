<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l31hi9byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l31hi9byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:credit-card" /></template>
