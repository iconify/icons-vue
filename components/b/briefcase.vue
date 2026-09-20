<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx0ln9bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx0ln9bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:briefcase" /></template>
