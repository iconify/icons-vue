<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8_rbj_tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w8_rbj_tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hospital-sign-square-remix" /></template>
