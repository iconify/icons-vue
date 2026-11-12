<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvtfe-rmr.css';
import '../../css/a/a746rccmm.css';
import '../../css/h/hsflg_a-k.css';
import '../../css/e/euha5s-mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yvtfe-rmr"/><path class="a746rccmm"/><path class="hsflg_a-k"/><circle class="euha5s-mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docsight-light" /></template>
