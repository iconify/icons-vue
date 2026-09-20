<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynw1a_xpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ynw1a_xpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cleaning-room-woman-remix" /></template>
