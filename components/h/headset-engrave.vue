<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xzk3ecj6k.css';
import '../../css/h/hegkb1m4u.css';
import '../../css/c/cvk-bup-z.css';
import '../../css/a/alwzv4b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xzk3ecj6k"/><path class="hegkb1m4u wm-shadow"/><path class="cvk-bup-z"/><path class="alwzv4b_p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:headset-engrave" /></template>
