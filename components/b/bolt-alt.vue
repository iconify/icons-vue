<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb2zonbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sb2zonbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bolt-alt" /></template>
