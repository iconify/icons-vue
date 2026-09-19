<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl4cs1byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fl4cs1byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-minus-20-solid" /></template>
