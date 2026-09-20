<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igc66db3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igc66db3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-4-line" /></template>
