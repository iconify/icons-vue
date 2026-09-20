<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceag4wngd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceag4wngd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:foggy-fill" /></template>
