<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrscrbb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zrscrbb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:body" /></template>
