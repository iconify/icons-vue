<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox73mjaja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox73mjaja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-information-variant" /></template>
