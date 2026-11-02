<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp0427blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp0427blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-crack-line" /></template>
