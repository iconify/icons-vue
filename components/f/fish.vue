<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyzz2jbxp.css';
import '../../css/s/sh9luzbpl.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/y/y957gubxe.css';
import '../../css/v/vmjs3ab-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yyzz2jbxp"/><path class="sh9luzbpl"/><g class="jn8qy4bru"><path class="y957gubxe"/><path class="vmjs3ab-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:fish" /></template>
