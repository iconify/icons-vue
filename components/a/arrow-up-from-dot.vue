<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i61sq0mfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i61sq0mfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-from-dot" /></template>
