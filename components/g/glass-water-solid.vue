<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtu15_roz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtu15_roz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:glass-water-solid" /></template>
