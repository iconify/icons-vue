<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7p_ssbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7p_ssbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-right-down" /></template>
