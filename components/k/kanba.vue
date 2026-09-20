<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxv007l0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nxv007l0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kanba" /></template>
