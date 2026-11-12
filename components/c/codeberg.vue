<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stui2mbih.css';
import '../../css/b/bzk26nqsg.css';
import '../../css/l/llcf3srjo.css';
import '../../css/r/rnqpocbhp.css';
import '../../css/y/y113rzbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGt8xDWdVB" x1="254.7" x2="419.3" y1="132.2" y2="460.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".495" class="bzk26nqsg"/><stop offset="1" class="llcf3srjo"/></linearGradient><path fill="url(#SVGt8xDWdVB)" class="rnqpocbhp"/><path class="y113rzbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codeberg" /></template>
