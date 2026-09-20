<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa3p8cgmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa3p8cgmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-big-up-sharp" /></template>
