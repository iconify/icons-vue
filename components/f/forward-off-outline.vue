<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix1cghcpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix1cghcpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:forward-off-outline" /></template>
