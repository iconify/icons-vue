<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/a/azmt7fbec.css';
import '../../css/h/h6i762oyw.css';
import '../../css/s/sq30kocpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="azmt7fbec"/><path class="h6i762oyw"/><path class="sq30kocpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:envelope-open-note" /></template>
