<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m8netx35k.css';
import '../../css/p/pve7dkb2j.css';
import '../../css/q/qgl0b2pvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m8netx35k"/><path class="pve7dkb2j"/><path class="qgl0b2pvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-shake-line-duotone" /></template>
