<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbsvtbcxs.css';
import '../../css/r/raqx0nmsd.css';
import '../../css/a/aaaoe8b6g.css';
import '../../css/i/ii1y0ubpf.css';
import '../../css/i/icck6s-3q.css';
import '../../css/u/uej208bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nbsvtbcxs"/><path class="raqx0nmsd"/><path class="aaaoe8b6g"/><path class="ii1y0ubpf"/><path class="icck6s-3q"/><path class="uej208bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-cassandra" /></template>
