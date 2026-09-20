<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3vcaebym.css';
import '../../css/n/nqbpfg7cv.css';
import '../../css/l/lwvi9hbvi.css';
import '../../css/h/hgiin5bmx.css';
import '../../css/k/khk6bxm_r.css';
import '../../css/y/y_z2w6clv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w3vcaebym"/><path class="nqbpfg7cv"/><path class="lwvi9hbvi"/><path class="hgiin5bmx"/><path class="khk6bxm_r"/><path class="y_z2w6clv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buildbot-dark" /></template>
