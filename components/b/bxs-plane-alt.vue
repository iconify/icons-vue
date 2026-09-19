<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfr71u25j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfr71u25j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-plane-alt" /></template>
