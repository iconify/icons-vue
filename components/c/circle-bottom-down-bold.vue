<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj1s-63ya.css';
import '../../css/u/u2tnche2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj1s-63ya"/><path class="u2tnche2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-bottom-down-bold" /></template>
