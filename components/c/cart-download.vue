<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s31t99skb.css';
import '../../css/u/uii4avzkv.css';
import '../../css/d/drt_omb2n.css';
import '../../css/v/vi7rz9k8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="s31t99skb"/><circle class="uii4avzkv"/><path class="drt_omb2n"/><path class="vi7rz9k8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cart-download" /></template>
