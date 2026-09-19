<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duhrwdb0w.css';
import '../../css/s/s31t99skb.css';
import '../../css/p/pvk172brt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duhrwdb0w"/><circle class="s31t99skb"/><circle class="pvk172brt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cart-alt" /></template>
