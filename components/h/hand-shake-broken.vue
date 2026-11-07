<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tf_xfjxyi.css';
import '../../css/r/rwyyhnb2f.css';
import '../../css/s/s76b8cctz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tf_xfjxyi"/><path class="rwyyhnb2f"/><path class="s76b8cctz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-shake-broken" /></template>
