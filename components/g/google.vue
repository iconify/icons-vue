<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jwgpxoo3x.css';
import '../../css/t/tk71-d9_p.css';
import '../../css/d/dm3lzbbtn.css';
import '../../css/j/jvu_1rs4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jwgpxoo3x"/><path class="tk71-d9_p"/><path class="dm3lzbbtn"/><path class="jvu_1rs4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:google" /></template>
