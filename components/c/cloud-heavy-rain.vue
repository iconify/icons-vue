<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/runo8_caf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="runo8_caf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cloud-heavy-rain" /></template>
