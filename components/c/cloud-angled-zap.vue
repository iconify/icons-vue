<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu_bbh2lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu_bbh2lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-angled-zap" /></template>
