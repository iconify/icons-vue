<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0pkalbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0pkalbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:check-all-bulk-round" /></template>
