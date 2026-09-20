<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ilef90r2i.css';
import '../../css/g/gp2un2bwc.css';
import '../../css/m/m6eplnbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ilef90r2i"/><path class="gp2un2bwc"/><path class="m6eplnbnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:keyboard-flat" /></template>
