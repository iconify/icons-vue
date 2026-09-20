<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgb2efl3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hgb2efl3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hide-layer-remix" /></template>
