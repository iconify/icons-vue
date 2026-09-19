<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgw_3z_ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vgw_3z_ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:baseball-glove" /></template>
