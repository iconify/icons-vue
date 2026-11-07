<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp600_i4z.css';
import '../../css/o/osemxebgc.css';
import '../../css/j/jy0yf6bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp600_i4z"/><path clip-rule="evenodd" class="osemxebgc"/><path class="jy0yf6bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-charge-minimalistic-outline" /></template>
