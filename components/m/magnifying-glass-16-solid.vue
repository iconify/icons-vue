<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjvbvt49c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fjvbvt49c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:magnifying-glass-16-solid" /></template>
