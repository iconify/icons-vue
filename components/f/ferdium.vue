<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lntkaob4s.css';
import '../../css/p/pc_b7vbqs.css';
import '../../css/i/iycln-b8i.css';
import '../../css/i/icywm0byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGn2j6wbdb" x1="81.9" x2="430.5" y1="442.6" y2="69" gradientUnits="userSpaceOnUse"><stop offset="0" class="lntkaob4s"/><stop offset="1" class="pc_b7vbqs"/></linearGradient><circle fill="url(#SVGn2j6wbdb)" class="iycln-b8i"/><path class="icywm0byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferdium" /></template>
