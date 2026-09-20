<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/m/m8k3h8pds.css';
import '../../css/z/zp6wnrbdq.css';
import '../../css/k/kjcpkzwgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="m8k3h8pds"/><path class="zp6wnrbdq"/><path class="kjcpkzwgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:add-playlist" /></template>
