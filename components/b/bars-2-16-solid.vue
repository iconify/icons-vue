<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnfvhmycx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tnfvhmycx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-2-16-solid" /></template>
