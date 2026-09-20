<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ay49rbbdp.css';
import '../../css/r/rc_eaccxy.css';
import '../../css/e/ejdkgccas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ay49rbbdp"/><path class="rc_eaccxy"/><path class="ejdkgccas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-like-broken" /></template>
