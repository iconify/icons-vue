<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpgnzm0ee.css';
import '../../css/q/qceextqrn.css';
import '../../css/m/mdb2_kuhb.css';
import '../../css/p/pnyyfkb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bpgnzm0ee"/><ellipse class="qceextqrn"/><path class="mdb2_kuhb"/><path class="pnyyfkb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:candle" /></template>
