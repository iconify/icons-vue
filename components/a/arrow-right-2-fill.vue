<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idf2qgbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idf2qgbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-2-fill" /></template>
