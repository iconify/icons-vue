<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc1rzpn4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc1rzpn4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-inbox" /></template>
