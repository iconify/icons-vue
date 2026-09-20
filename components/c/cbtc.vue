<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5nnxi_tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5nnxi_tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cbtc" /></template>
