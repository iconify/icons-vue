<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em5g3mbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em5g3mbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-quote-close" /></template>
