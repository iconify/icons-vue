<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da6q-edbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da6q-edbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cloud-sun" /></template>
