<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leg00xbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leg00xbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-refresh" /></template>
