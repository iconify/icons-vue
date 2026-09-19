<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/os_tdyjga.css';
import '../../css/g/gcohp_b3e.css';
import '../../css/n/ndz3s8e5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="os_tdyjga"/><path class="gcohp_b3e"/><path class="ndz3s8e5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:door" /></template>
