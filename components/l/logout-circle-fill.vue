<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxav8w73h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxav8w73h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:logout-circle-fill" /></template>
