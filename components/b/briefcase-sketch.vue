<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k3k-_vkxl.css';
import '../../css/k/kmgkpdb0r.css';
import '../../css/p/pfitmhbyp.css';
import '../../css/r/rk_aglbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k3k-_vkxl"/><path class="kmgkpdb0r wm-a"/><path class="pfitmhbyp wm-k"/><path class="rk_aglbyi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:briefcase-sketch" /></template>
