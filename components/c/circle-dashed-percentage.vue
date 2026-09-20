<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5ps2pbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5ps2pbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-percentage" /></template>
