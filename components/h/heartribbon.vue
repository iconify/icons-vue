<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwsggl4nt.css';
import '../../css/w/w2kpx3bru.css';
import '../../css/b/bajemy94v.css';
import '../../css/v/vfdxbdcpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwsggl4nt"/><path class="w2kpx3bru"/><path class="bajemy94v"/><path class="vfdxbdcpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heartribbon" /></template>
