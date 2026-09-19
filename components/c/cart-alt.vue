<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmgue-b6m.css';
import '../../css/s/s31t99skb.css';
import '../../css/p/pvk172brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmgue-b6m"/><circle class="s31t99skb"/><circle class="pvk172brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cart-alt" /></template>
