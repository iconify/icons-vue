<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_zpebgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf_zpebgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-filled" /></template>
