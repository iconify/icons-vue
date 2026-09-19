<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zajvw9b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zajvw9b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:cloud-saved" /></template>
