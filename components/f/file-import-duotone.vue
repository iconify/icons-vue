<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdg5s2amp.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z8zu7p64g.css';
import '../../css/w/wkck6fb3i.css';
import '../../css/m/mc2zb0bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGHwRGdWeY" class="rdg5s2amp"/></defs><g class="ft5dv1b6b"><path class="z8zu7p64g"/><use href="#SVGHwRGdWeY"/><path class="wkck6fb3i"/><use href="#SVGHwRGdWeY" class="mc2zb0bvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:file-import-duotone" /></template>
