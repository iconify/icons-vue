<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js8pr3blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="js8pr3blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:italic-16-solid" /></template>
