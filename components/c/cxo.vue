<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcstgtvsf.css';
import '../../css/f/fbb_pv2ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcstgtvsf"/><path class="fbb_pv2ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cxo" /></template>
