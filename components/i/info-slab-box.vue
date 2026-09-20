<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7nr4tvvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7nr4tvvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:info-slab-box" /></template>
