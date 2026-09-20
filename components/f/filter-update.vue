<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p09x_hb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p09x_hb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:filter-update" /></template>
