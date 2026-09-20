<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldpbk6e6e.css';
import '../../css/f/fcu49sbmi.css';
import '../../css/r/r40zw-uer.css';
import '../../css/k/k1_tqxbhb.css';
import '../../css/k/ku75bab7r.css';
import '../../css/q/qup8t0bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldpbk6e6e"/><path class="fcu49sbmi"/><path class="r40zw-uer"/><path class="k1_tqxbhb"/><path class="ku75bab7r"/><path class="qup8t0bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghidra" /></template>
