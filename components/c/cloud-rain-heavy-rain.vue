<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-st2-zet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="n-st2-zet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cloud-rain-heavy-rain" /></template>
