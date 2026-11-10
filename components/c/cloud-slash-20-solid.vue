<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_a2bxboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y_a2bxboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-slash-20-solid" /></template>
