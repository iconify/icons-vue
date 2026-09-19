<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcfhbjb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hcfhbjb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heart-outline-24px" /></template>
