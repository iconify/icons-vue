<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/ypp_29btr.css';
import '../../css/g/gkxyxtbmf.css';
import '../../css/i/im7es_bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ypp_29btr"/><path class="gkxyxtbmf"/><path class="im7es_bhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:location-share-01" /></template>
