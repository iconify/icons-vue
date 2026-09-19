<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfefa3byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfefa3byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-collapse-vertical" /></template>
