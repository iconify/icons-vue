<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5os10bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="m5os10bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:balloon" /></template>
