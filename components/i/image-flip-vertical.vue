<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lds95vbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lds95vbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-flip-vertical" /></template>
