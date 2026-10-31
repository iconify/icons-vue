<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft3fdyb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft3fdyb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-minus-fill-round" /></template>
