<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_e9s3b0c.css';
import '../../css/p/pj_2zb4qu.css';
import '../../css/i/ie4mcb0dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_e9s3b0c"/><rect transform="rotate(45 307.788 204.2)" class="pj_2zb4qu"/><path class="ie4mcb0dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:eyedrop-outline" /></template>
