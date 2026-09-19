<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj3lf2btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":17};
const content = `<path class="tj3lf2btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:art-board" /></template>
