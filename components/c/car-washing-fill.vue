<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nho0z4byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nho0z4byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:car-washing-fill" /></template>
