<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph-l3p-7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph-l3p-7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:camera-foto-solid" /></template>
