<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/plmy2zvgw.css';
import '../../css/s/s5eh35bzd.css';
import '../../css/l/lzg1d1lbm.css';
import '../../css/q/qge1xjbzq.css';
import '../../css/j/js7gvq8hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="plmy2zvgw"/><path class="s5eh35bzd"/><path class="lzg1d1lbm"/><path class="qge1xjbzq"/><path class="js7gvq8hx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-wave-line-duotone" /></template>
