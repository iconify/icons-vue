<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2b_f4a6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2b_f4a6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-circle-three-quarter" /></template>
