<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4v10i-vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i4v10i-vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cochlear-implant-outline" /></template>
