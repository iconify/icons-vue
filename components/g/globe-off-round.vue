<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai8g9dlig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai8g9dlig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-off-round" /></template>
