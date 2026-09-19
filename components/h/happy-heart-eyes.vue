<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt0u17bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt0u17bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:happy-heart-eyes" /></template>
