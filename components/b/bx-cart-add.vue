<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s31t99skb.css';
import '../../css/u/uii4avzkv.css';
import '../../css/d/d2mvnsbwq.css';
import '../../css/a/ah0waennr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="s31t99skb"/><circle class="uii4avzkv"/><path class="d2mvnsbwq"/><path class="ah0waennr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cart-add" /></template>
