<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geimf9b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geimf9b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-start-on-rectangle" /></template>
