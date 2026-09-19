<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1s786g6g.css';
import '../../css/q/ql0g54bag.css';
import '../../css/a/ar__gdbwn.css';
import '../../css/g/gkts6gb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="r1s786g6g"/><circle class="ql0g54bag"/><path class="ar__gdbwn"/><path class="gkts6gb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-dynamic-route-server" /></template>
