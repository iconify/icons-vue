<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjxv-8b0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjxv-8b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-minus" /></template>
