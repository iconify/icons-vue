<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw1_f1dns.css';
import '../../css/w/w5t1ykp4g.css';
import '../../css/s/slveivbkv.css';
import '../../css/t/tlcbsubgk.css';
import '../../css/q/qopzznmys.css';
import '../../css/g/gep5gvj9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bw1_f1dns"/><path class="w5t1ykp4g"/><path class="slveivbkv"/><circle class="tlcbsubgk"/><path class="qopzznmys"/><path class="gep5gvj9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudreve" /></template>
