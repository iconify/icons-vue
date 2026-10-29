<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g2vmknnmt.css';
import '../../css/a/an74bxu4h.css';
import '../../css/o/o-ebpv9hq.css';
import '../../css/i/iy59935aw.css';
import '../../css/s/spi-7emnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g2vmknnmt"/><path class="an74bxu4h wm-shadow"/><path class="o-ebpv9hq"/><path class="iy59935aw"/><path class="spi-7emnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-person-glasses-engrave" /></template>
