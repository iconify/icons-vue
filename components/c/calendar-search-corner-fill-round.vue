<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzhfw9bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzhfw9bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-search-corner-fill-round" /></template>
