<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/ho-7xdd0k.css';
import '../../css/d/dv6re0b-t.css';
import '../../css/f/fg8gx3brw.css';
import '../../css/s/s8ro7484l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ho-7xdd0k"/><path class="dv6re0b-t"/><path class="fg8gx3brw"/><path class="s8ro7484l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-call-linear" /></template>
