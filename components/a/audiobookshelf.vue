<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wckns2brg.css';
import '../../css/i/if88er1fq.css';
import '../../css/r/rvcfnxbit.css';
import '../../css/k/k0cyj5-rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGI5k9oeBe" x1="255.5" x2="255.5" y1="991.4" y2="496.6" gradientTransform="matrix(1 0 0 -1 0 1000)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="wckns2brg"/><stop offset=".99" class="if88er1fq"/></linearGradient><circle fill="url(#SVGI5k9oeBe)" class="rvcfnxbit"/><path class="k0cyj5-rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiobookshelf" /></template>
