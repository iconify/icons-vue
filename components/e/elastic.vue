<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vku-3ub_z.css';
import '../../css/l/l5dckkl4f.css';
import '../../css/m/mtt1kdbry.css';
import '../../css/t/t-a9dukij.css';
import '../../css/n/nzay1dbcq.css';
import '../../css/j/j4lbajbaj.css';
import '../../css/s/sb58d8b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vku-3ub_z"/><path class="l5dckkl4f"/><path class="mtt1kdbry"/><path class="t-a9dukij"/><path class="nzay1dbcq"/><path class="j4lbajbaj"/><path class="sb58d8b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elastic" /></template>
