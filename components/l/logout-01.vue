<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az_tn_bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az_tn_bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:logout-01" /></template>
