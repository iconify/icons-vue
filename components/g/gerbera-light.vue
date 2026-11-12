<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-llkv2cb.css';
import '../../css/m/m-j3uabvn.css';
import '../../css/k/kckc1iwlf.css';
import '../../css/t/tder15a4e.css';
import '../../css/f/f6pkp8bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVG29KeZdAd" cx="256" cy="256" r="247.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="d-llkv2cb"/><stop offset=".853" class="m-j3uabvn"/><stop offset="1" class="kckc1iwlf"/></radialGradient><path fill="url(#SVG29KeZdAd)" class="tder15a4e"/><path class="f6pkp8bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gerbera-light" /></template>
