<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn9uzzb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rn9uzzb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hearing-deaf-1-remix" /></template>
