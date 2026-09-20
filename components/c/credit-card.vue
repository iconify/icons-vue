<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etpj0ljio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="etpj0ljio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:credit-card" /></template>
