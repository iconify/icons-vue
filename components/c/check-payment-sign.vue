<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cyyqt0pzv.css';
import '../../css/s/shua_zbkq.css';
import '../../css/x/xp50n6b6u.css';
import '../../css/t/t03j23bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cyyqt0pzv"/><path class="shua_zbkq"/><path class="xp50n6b6u"/><path class="t03j23bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:check-payment-sign" /></template>
