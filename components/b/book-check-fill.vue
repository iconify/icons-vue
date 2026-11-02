<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejmxj6bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejmxj6bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-check-fill" /></template>
