<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hawr1bc8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hawr1bc8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:eject" /></template>
