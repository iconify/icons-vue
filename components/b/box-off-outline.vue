<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk-ld7kbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk-ld7kbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-off-outline" /></template>
