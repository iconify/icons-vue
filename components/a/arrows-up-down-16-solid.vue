<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tal1vmb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tal1vmb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-up-down-16-solid" /></template>
