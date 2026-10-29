<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eozdlk4zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eozdlk4zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-crack-solid" /></template>
