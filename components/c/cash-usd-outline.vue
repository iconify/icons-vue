<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tykd_mbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tykd_mbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-usd-outline" /></template>
