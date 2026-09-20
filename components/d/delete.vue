<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftfbryb0n.css';
import '../../css/p/pfc59dpqc.css';
import '../../css/u/ufnun_9wh.css';
import '../../css/u/ucp_klm1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ftfbryb0n"/><path class="pfc59dpqc"/><path class="ufnun_9wh"/><path class="ucp_klm1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:delete" /></template>
