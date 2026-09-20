<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icg6lubjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icg6lubjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-2-fill" /></template>
