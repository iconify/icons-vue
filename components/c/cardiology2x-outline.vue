<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxgrdzc_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mxgrdzc_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cardiology2x-outline" /></template>
