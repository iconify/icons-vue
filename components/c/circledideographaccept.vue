<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsize-wde.css';
import '../../css/n/nw8rr6bkb.css';
import '../../css/b/bl-vv4mlh.css';
import '../../css/m/mp_j2rb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="wsize-wde"/><path class="nw8rr6bkb"/><path class="bl-vv4mlh"/><path class="mp_j2rb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:circledideographaccept" /></template>
