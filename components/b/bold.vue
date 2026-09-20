<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4epcpbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4epcpbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bold" /></template>
