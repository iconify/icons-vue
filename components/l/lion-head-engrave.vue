<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n9zsydh4v.css';
import '../../css/c/c_gd-ksmn.css';
import '../../css/a/aozp2s1mk.css';
import '../../css/e/ewbtvpc_j.css';
import '../../css/w/w9p-5cc-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n9zsydh4v wm-k"/><path class="c_gd-ksmn wm-shadow"/><path class="aozp2s1mk wm-k"/><path class="ewbtvpc_j wm-a"/><path class="w9p-5cc-x wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lion-head-engrave" /></template>
