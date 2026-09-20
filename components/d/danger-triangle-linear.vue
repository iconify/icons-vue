<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fa643866d.css';
import '../../css/e/evd_udn_h.css';
import '../../css/p/pr1jznbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fa643866d"/><path class="evd_udn_h"/><path class="pr1jznbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-triangle-linear" /></template>
