<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp7xi2uve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp7xi2uve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:archive-sharp" /></template>
