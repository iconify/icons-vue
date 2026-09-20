<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfmaj0bsk.css';
import '../../css/p/pcqj9r9mm.css';
import '../../css/o/od92dhlsp.css';
import '../../css/r/r2zs8ibbn.css';
import '../../css/f/fqgdc-bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGMmwKCbws" x1="-703.737" x2="-703.263" y1="796" y2="796" gradientTransform="matrix(0 1080 1080 0 -859424 760036)" gradientUnits="userSpaceOnUse"><stop offset="0" class="kfmaj0bsk"/><stop offset="1" class="pcqj9r9mm"/></linearGradient><path fill="url(#SVGMmwKCbws)" class="od92dhlsp"/><path class="r2zs8ibbn"/><path class="fqgdc-bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:espconnect" /></template>
