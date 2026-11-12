<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfv7kibpo.css';
import '../../css/d/dfc5wbcbr.css';
import '../../css/u/u_l71ebni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfv7kibpo"/><path class="dfc5wbcbr"/><path class="u_l71ebni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-mail-dark" /></template>
