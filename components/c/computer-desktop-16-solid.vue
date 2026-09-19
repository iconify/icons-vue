<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_i0wab7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e_i0wab7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:computer-desktop-16-solid" /></template>
