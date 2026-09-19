<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6isgs9fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m6isgs9fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-check-20-solid" /></template>
