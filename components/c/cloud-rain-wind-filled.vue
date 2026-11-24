<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhblkjbdv.css';
import '../../css/s/stisajbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhblkjbdv"/><path class="stisajbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-rain-wind-filled" /></template>
