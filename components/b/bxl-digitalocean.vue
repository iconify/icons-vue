<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl2ih_b2x.css';
import '../../css/q/qrgcibvkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl2ih_b2x"/><path class="qrgcibvkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-digitalocean" /></template>
