<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/n/na-2c5b9l.css';
import '../../css/f/fo6b1pbaj.css';
import '../../css/d/d1j8upbii.css';
import '../../css/f/fa9fp7biw.css';
import '../../css/w/w2tnaoa4j.css';
import '../../css/r/rcoybwbzr.css';
import '../../css/f/fh6ao6bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVG2dpZiexT" cx=".35" cy=".3" r=".8"><stop offset="0" class="vc--wpv5i"/><stop offset=".25" class="na-2c5b9l"/><stop offset=".8" class="fo6b1pbaj"/><stop offset="1" class="d1j8upbii"/></radialGradient></defs><g transform="matrix(4.2 0 0 4.2 256 275.2)"><path fill="url(#SVG2dpZiexT)" class="fa9fp7biw"/><ellipse transform="rotate(-35 -27 -33)" class="w2tnaoa4j"/></g><path class="rcoybwbzr"/><path class="fh6ao6bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:heart-with-ribbon" /></template>
