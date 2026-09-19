<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6_fg-lkg.css';
import '../../css/i/i9urgub_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6_fg-lkg"/><path class="i9urgub_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-right-stroke-square-filled" /></template>
