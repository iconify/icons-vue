<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-c80ro0i.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/t/tszz_sbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGoNspOeJX" x1="110.4" x2="401.6" y1="3.7" y2="508.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="f-c80ro0i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGoNspOeJX)" class="tszz_sbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:littlelink-light" /></template>
