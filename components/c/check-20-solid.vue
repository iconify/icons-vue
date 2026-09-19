<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvw-irbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="dvw-irbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:check-20-solid" /></template>
