<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9-7gieeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9-7gieeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:delete-sharp" /></template>
