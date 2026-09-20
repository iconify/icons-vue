<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfh3jn-hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfh3jn-hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-scan-outline" /></template>
