<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud98ozx5d.css';
import '../../css/i/i9d11l03r.css';
import '../../css/a/afd0d2byl.css';
import '../../css/a/avx17yb5a.css';
import '../../css/v/vfgpd_bhg.css';
import '../../css/h/hsk4i315p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGmmNLac9p" x1="16.181" x2="16.181" y1="28.39" y2="5.61" gradientTransform="translate(0 45.903)scale(1.06453)" gradientUnits="userSpaceOnUse"><stop class="ud98ozx5d"/><stop offset="1" class="i9d11l03r"/></linearGradient></defs><path class="afd0d2byl"/><path class="avx17yb5a"/><path fill="url(#SVGmmNLac9p)" class="vfgpd_bhg"/><path class="hsk4i315p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:insomnia-wordmark" /></template>
