<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj5tz6q7m.css';
import '../../css/m/mhyryyb4e.css';
import '../../css/l/lp2p1ll7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj5tz6q7m"/><path class="mhyryyb4e"/><path class="lp2p1ll7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:atpay" /></template>
