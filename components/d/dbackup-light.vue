<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mekzb_ebz.css';
import '../../css/e/e8_gbpbab.css';
import '../../css/p/pvdz305lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mekzb_ebz"/><path class="e8_gbpbab"/><path class="pvdz305lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dbackup-light" /></template>
