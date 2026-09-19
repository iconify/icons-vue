<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh2o-wywp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="wh2o-wywp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-thick-right" /></template>
