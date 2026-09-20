<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvky8xb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvky8xb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:h-4" /></template>
