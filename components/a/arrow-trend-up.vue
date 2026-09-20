<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyq_gi3cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyq_gi3cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:arrow-trend-up" /></template>
