<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr1y3kbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr1y3kbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-currency-rupee-solid" /></template>
