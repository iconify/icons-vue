<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivg8c9bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ivg8c9bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:earth" /></template>
