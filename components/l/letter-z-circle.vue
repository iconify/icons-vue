<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii6adt7xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii6adt7xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-z-circle" /></template>
