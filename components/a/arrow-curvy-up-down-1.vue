<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5996na3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u5996na3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-curvy-up-down-1" /></template>
