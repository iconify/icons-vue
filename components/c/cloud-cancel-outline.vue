<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdp-fub5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdp-fub5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-cancel-outline" /></template>
