<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj78ek-bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sj78ek-bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:drone-outline-24px" /></template>
