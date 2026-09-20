<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otvdx4b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otvdx4b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:atom" /></template>
