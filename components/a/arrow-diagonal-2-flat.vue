<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgnaupfol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fgnaupfol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:arrow-diagonal-2-flat" /></template>
