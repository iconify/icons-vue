<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er6yahbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="er6yahbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-3-20-solid" /></template>
