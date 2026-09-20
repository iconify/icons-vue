<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rogi63pbf.css';
import '../../css/b/b8vu5kbki.css';
import '../../css/s/sq7mu2v-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rogi63pbf"/><path class="b8vu5kbki"/><path class="sq7mu2v-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balloon-line-duotone" /></template>
