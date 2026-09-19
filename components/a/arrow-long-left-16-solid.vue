<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkdsnacom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nkdsnacom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-left-16-solid" /></template>
