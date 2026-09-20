<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sll_zg-uo.css';
import '../../css/k/k2249mt9o.css';
import '../../css/v/v9u8nhb5n.css';
import '../../css/y/y5rf2kbmf.css';
import '../../css/b/b2cn8fb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGw4Zcvc8v" cx="255.998" cy="256" r="247.406" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset=".853" class="k2249mt9o"/><stop offset="1" class="v9u8nhb5n"/></radialGradient><path fill="url(#SVGw4Zcvc8v)" class="y5rf2kbmf"/><path class="b2cn8fb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gerbera-dark" /></template>
