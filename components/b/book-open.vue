<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygai0mmxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygai0mmxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:book-open" /></template>
