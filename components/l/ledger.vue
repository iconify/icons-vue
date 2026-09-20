<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh2z-ib6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh2z-ib6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ledger" /></template>
