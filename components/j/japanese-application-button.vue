<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxw7g3bdf.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/j/jpuqunpzd.css';
import '../../css/x/xwhsq3b5z.css';
import '../../css/h/hwsqkibfd.css';
import '../../css/a/a99-j3b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kxw7g3bdf"/><g class="sxsjrzbyv"><path clip-rule="evenodd" class="jpuqunpzd"/><path clip-rule="evenodd" transform="matrix(.2737 0 0 .269 -374.937 -95.373)" class="xwhsq3b5z"/><path clip-rule="evenodd" class="hwsqkibfd"/><path class="a99-j3b_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:japanese-application-button" /></template>
