<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/s/ss97z95ca.css';
import '../../css/t/thxavqb2a.css';
import '../../css/d/d1j8upbii.css';
import '../../css/f/fa9fp7biw.css';
import '../../css/w/w2tnaoa4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGhXdf17GS" cx=".35" cy=".3" r=".8"><stop offset="0" class="vc--wpv5i"/><stop offset=".25" class="ss97z95ca"/><stop offset=".8" class="thxavqb2a"/><stop offset="1" class="d1j8upbii"/></radialGradient></defs><g transform="matrix(4.2 0 0 4.2 256 275.2)"><path fill="url(#SVGhXdf17GS)" class="fa9fp7biw"/><ellipse transform="rotate(-35 -27 -33)" class="w2tnaoa4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:brown-heart" /></template>
