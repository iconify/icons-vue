<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc3t8iprc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc3t8iprc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layers-minus-fill" /></template>
