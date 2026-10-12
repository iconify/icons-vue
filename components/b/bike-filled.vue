<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm73iyntv.css';
import '../../css/y/ywrez9dnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm73iyntv"/><path class="ywrez9dnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bike-filled" /></template>
