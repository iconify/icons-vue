<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdc_cacgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdc_cacgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:folder-sharp" /></template>
