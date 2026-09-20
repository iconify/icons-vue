<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1q1spe1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1q1spe1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:b4x" /></template>
