<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_k-y-sek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_k-y-sek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:left-top-arrow-circle" /></template>
