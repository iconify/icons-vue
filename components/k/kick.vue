<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olles1bul.css';
import '../../css/w/wjjc-obre.css';
import '../../css/c/c1o96w75g.css';
import '../../css/g/g2mvkvbrd.css';
import '../../css/o/oi_sgi21y.css';
import '../../css/r/rr0-n0bif.css';
import '../../css/b/b815hcbjd.css';
import '../../css/p/pha3a919q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olles1bul"/><path class="wjjc-obre"/><path class="c1o96w75g"/><path class="g2mvkvbrd"/><path class="oi_sgi21y"/><path class="rr0-n0bif"/><path class="b815hcbjd"/><path class="pha3a919q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kick" /></template>
