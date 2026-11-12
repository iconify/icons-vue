<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dif6p1bms.css';
import '../../css/u/u1-7rbomv.css';
import '../../css/s/smgw8kb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dif6p1bms"/><path class="u1-7rbomv"/><path class="smgw8kb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deluge" /></template>
