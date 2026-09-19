<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/p/pshr00bvs.css';
import '../../css/v/vw7nbibyx.css';
import '../../css/o/okzjhjbnf.css';
import '../../css/m/mv0xm5bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGop6VgDeN" cx="93.44" cy="1113.51" r="69.83" gradientTransform="matrix(1 0 0 -1 0 1148.01)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="pshr00bvs"/></radialGradient></defs><path class="vw7nbibyx"/><path class="okzjhjbnf"/><path fill="url(#SVGop6VgDeN)" class="mv0xm5bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ceylon" /></template>
