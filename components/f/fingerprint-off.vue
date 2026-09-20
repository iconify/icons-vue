<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc-zombxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc-zombxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fingerprint-off" /></template>
