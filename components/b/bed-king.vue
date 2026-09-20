<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddo390ave.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddo390ave"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bed-king" /></template>
