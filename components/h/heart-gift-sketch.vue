<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pjyv6h2rt.css';
import '../../css/n/n95lt7x7t.css';
import '../../css/r/r1rrqobgd.css';
import '../../css/m/mi_9ztbfv.css';
import '../../css/z/zoq86zjqi.css';
import '../../css/v/vz-n80b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pjyv6h2rt"/><path class="n95lt7x7t wm-a"/><path class="r1rrqobgd wm-s"/><path class="mi_9ztbfv wm-k"/><path class="wm-a zoq86zjqi"/><path class="vz-n80b1y wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-gift-sketch" /></template>
