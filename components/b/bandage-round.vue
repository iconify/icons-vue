<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uik04_m9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uik04_m9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bandage-round" /></template>
