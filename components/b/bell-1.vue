<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-nft1xhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-nft1xhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bell-1" /></template>
