<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdg5s2amp.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pnlw9tbfh.css';
import '../../css/w/wkck6fb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGHwRGdWeY" class="rdg5s2amp"/></defs><g class="ft5dv1b6b"><path class="pnlw9tbfh"/><use href="#SVGHwRGdWeY"/><path class="wkck6fb3i"/><use href="#SVGHwRGdWeY"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:file-import-solid" /></template>
