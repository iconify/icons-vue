<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvxof8u4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvxof8u4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:heading-h3" /></template>
