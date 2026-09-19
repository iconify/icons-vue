<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs-ujmdie.css';
import '../../css/f/fwixbousw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs-ujmdie"/><path class="fwixbousw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:exposure-filled" /></template>
