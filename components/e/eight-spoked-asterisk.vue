<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg7xajeea.css';
import '../../css/x/xcwpqnbkb.css';
import '../../css/l/lo4d7r9dr.css';
import '../../css/d/dkwexcp4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yg7xajeea"/><path class="xcwpqnbkb"/><path class="lo4d7r9dr"/><path class="dkwexcp4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:eight-spoked-asterisk" /></template>
