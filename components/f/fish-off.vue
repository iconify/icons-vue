<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbiy5tpwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbiy5tpwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fish-off" /></template>
