<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iny_z7-rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="iny_z7-rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gamepad-bold" /></template>
