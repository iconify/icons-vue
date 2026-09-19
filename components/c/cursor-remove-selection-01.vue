<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiszgubkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiszgubkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-remove-selection-01" /></template>
