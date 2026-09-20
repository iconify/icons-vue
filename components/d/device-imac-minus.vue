<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw6l6rbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw6l6rbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-minus" /></template>
