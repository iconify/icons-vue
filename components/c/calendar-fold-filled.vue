<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnhz2ikjq.css';
import '../../css/w/wd_x4i40e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnhz2ikjq"/><path class="wd_x4i40e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-fold-filled" /></template>
