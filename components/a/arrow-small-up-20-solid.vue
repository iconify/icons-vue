<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_goi9h2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k_goi9h2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-up-20-solid" /></template>
