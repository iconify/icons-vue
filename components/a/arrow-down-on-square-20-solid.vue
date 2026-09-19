<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clpqvbb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="clpqvbb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-on-square-20-solid" /></template>
