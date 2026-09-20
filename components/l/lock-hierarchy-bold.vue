<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyqv2ybri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyqv2ybri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:lock-hierarchy-bold" /></template>
