<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2rdiachu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g2rdiachu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-up-20-solid" /></template>
