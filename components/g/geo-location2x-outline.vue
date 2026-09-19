<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1wz_ibso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w1wz_ibso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:geo-location2x-outline" /></template>
