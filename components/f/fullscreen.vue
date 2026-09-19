<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv1ssxzig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="wv1ssxzig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:fullscreen" /></template>
