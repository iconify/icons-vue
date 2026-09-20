<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt-9l2bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt-9l2bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:inbox-arrow-up" /></template>
