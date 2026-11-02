<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3zrrmk8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3zrrmk8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folding-fan-fill" /></template>
