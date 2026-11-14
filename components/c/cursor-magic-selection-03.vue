<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn69s8bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn69s8bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-magic-selection-03" /></template>
