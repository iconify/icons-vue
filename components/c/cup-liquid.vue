<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piz8b0-cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piz8b0-cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cup-liquid" /></template>
