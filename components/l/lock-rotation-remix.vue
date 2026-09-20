<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pge5z1bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pge5z1bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lock-rotation-remix" /></template>
