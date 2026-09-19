<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-gq3s8at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k-gq3s8at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bars-4" /></template>
