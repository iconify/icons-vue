<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u-2zzdyrk.css';
import '../../css/r/rmzvr0rnp.css';
import '../../css/l/lvpeqwbwj.css';
import '../../css/l/ldqvx2utm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u-2zzdyrk"/><path class="rmzvr0rnp wm-a"/><path class="lvpeqwbwj wm-k"/><path class="ldqvx2utm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gift-sketch" /></template>
