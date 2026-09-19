<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktp18214b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktp18214b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:low-vision-outline-24px" /></template>
