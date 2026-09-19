<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_n-zcbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_n-zcbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-01" /></template>
