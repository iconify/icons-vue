<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjp_koc1i.css';
import '../../css/l/l6yehs63f.css';
import '../../css/g/ghhg-0_2c.css';
import '../../css/u/uj_9lubin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjp_koc1i"/><path class="l6yehs63f"/><circle class="ghhg-0_2c"/><path class="uj_9lubin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lollipop" /></template>
