<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kofyy-e0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kofyy-e0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-angle-outline" /></template>
