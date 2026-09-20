<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liz-yrx3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="liz-yrx3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-alt-line" /></template>
