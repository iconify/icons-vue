<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw_m1l2te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw_m1l2te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:colors" /></template>
