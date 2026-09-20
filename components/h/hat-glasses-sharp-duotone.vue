<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/r/rc4l1o1iu.css';
import '../../css/l/laouckjiw.css';
import '../../css/h/hgkgp9enu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rc4l1o1iu"/><path clip-rule="evenodd" class="laouckjiw"/><path class="hgkgp9enu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hat-glasses-sharp-duotone" /></template>
