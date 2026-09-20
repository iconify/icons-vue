<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtd-oqb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtd-oqb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:house-outline" /></template>
