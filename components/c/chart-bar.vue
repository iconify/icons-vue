<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-7u2gbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-7u2gbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chart-bar" /></template>
