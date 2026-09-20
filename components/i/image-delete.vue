<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erqvyrbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erqvyrbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:image-delete" /></template>
