<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty8ngujmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ty8ngujmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:graduation-cap-remix" /></template>
