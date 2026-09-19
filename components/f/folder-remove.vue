<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/x/xrfbgub3m.css';
import '../../css/r/r0lwmzbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<g class="n1lsf0bnc"><path class="xrfbgub3m"/><path class="r0lwmzbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:folder-remove" /></template>
