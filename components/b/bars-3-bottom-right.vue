<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_k2hhb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m_k2hhb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bars-3-bottom-right" /></template>
