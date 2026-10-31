<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3ye0t2rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ye0t2rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-left-large-bulk-round" /></template>
