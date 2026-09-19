<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-3v2hqse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h-3v2hqse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-uturn-up" /></template>
