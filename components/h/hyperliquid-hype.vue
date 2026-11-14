<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z044ykbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z044ykbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hyperliquid-hype" /></template>
