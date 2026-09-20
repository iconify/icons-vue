<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy2u80b4g.css';
import '../../css/k/kk1809b4e.css';
import '../../css/z/zcl8rmben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oy2u80b4g"/><path class="kk1809b4e"/><path class="zcl8rmben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceplane" /></template>
