<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/ruztbtuvn.css';
import '../../css/v/vs28pnhuh.css';
import '../../css/c/cff9xkc9z.css';
import '../../css/u/ugjt2qb1i.css';
import '../../css/j/j6an-7elt.css';
import '../../css/u/u5jri5j7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ruztbtuvn wm-k"/><path class="vs28pnhuh wm-a"/><path class="cff9xkc9z wm-s"/><path class="ugjt2qb1i wm-k"/><path class="j6an-7elt wm-a"/><path class="u5jri5j7y wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-off-sketch" /></template>
