<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd88nzbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd88nzbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-hand-up" /></template>
