<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d10gvkb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d10gvkb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-library-20-solid" /></template>
