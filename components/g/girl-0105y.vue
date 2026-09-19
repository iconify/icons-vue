<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud4eghbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ud4eghbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:girl-0105y" /></template>
