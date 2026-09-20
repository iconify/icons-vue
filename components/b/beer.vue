<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/orvuzw1eu.css';
import '../../css/p/pfm0_8fry.css';
import '../../css/c/c8q0b5a8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="orvuzw1eu"/><path class="pfm0_8fry"/><path class="c8q0b5a8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:beer" /></template>
