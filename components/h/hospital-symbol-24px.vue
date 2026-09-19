<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctd5_sb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctd5_sb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hospital-symbol-24px" /></template>
