<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rslo40inv.css';
import '../../css/r/rwsq_83pk.css';
import '../../css/w/warcgn-bq.css';
import '../../css/o/ov0_cbb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rslo40inv"/><path class="rwsq_83pk"/><path class="warcgn-bq"/><path class="ov0_cbb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:creditcard" /></template>
