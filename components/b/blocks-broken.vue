<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vq8p2ub8p.css';
import '../../css/f/fwkjzlc8s.css';
import '../../css/s/s8egyjbkm.css';
import '../../css/z/zjt4gb9yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vq8p2ub8p"/><path class="fwkjzlc8s"/><path class="s8egyjbkm"/><path class="zjt4gb9yw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:blocks-broken" /></template>
