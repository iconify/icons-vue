<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8pp2tbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u8pp2tbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:email-stroke-12" /></template>
