<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yszr0-bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yszr0-bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:footprints" /></template>
