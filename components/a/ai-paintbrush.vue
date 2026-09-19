<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwq8uec-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwq8uec-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-paintbrush" /></template>
