<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn_mjmb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wn_mjmb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-round-x14" /></template>
