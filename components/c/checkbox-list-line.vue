<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkmrf7nug.css';
import '../../css/l/lv3lunbbq.css';
import '../../css/p/payqcba1p.css';
import '../../css/q/qrjl8uhao.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 hkmrf7nug"/><path class="clr-i-outline clr-i-outline-path-2 lv3lunbbq"/><path class="clr-i-outline clr-i-outline-path-3 payqcba1p"/><path class="clr-i-outline clr-i-outline-path-4 qrjl8uhao"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:checkbox-list-line" /></template>
