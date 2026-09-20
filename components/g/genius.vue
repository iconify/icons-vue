<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu7v-1qzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu7v-1qzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:genius" /></template>
