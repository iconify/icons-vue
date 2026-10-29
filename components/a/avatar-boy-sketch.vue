<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nco5g-rav.css';
import '../../css/y/ymnvc_coe.css';
import '../../css/s/sz8giyy7i.css';
import '../../css/r/ri7rjxmdv.css';
import '../../css/o/or5qoybza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nco5g-rav wm-k"/><path class="wm-k ymnvc_coe"/><path class="sz8giyy7i wm-k"/><path class="ri7rjxmdv wm-k"/><path class="or5qoybza wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-boy-sketch" /></template>
