<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqhip8bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqhip8bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:discount-percent-fire-remix" /></template>
