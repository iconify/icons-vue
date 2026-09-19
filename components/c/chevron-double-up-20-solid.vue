<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c47vcyzsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c47vcyzsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-up-20-solid" /></template>
