<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikn_s50ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikn_s50ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-6-fill-round" /></template>
