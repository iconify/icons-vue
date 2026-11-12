<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf4cxs7wl.css';
import '../../css/p/p4ue24b-l.css';
import '../../css/i/ir4rni1pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kf4cxs7wl"/><path class="p4ue24b-l"/><path class="ir4rni1pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adguardhome-sync" /></template>
