<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8-47p4hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8-47p4hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circuit-board-filled" /></template>
