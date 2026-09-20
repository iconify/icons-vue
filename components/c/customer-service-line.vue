<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-3zwldxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-3zwldxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:customer-service-line" /></template>
