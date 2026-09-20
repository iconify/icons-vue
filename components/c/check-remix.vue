<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh1ttob6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rh1ttob6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:check-remix" /></template>
