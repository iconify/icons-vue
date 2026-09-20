<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyaa1ib5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyaa1ib5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-search" /></template>
