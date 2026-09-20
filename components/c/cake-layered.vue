<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxv23u_pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxv23u_pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cake-layered" /></template>
