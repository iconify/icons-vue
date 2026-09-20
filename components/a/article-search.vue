<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltam8gb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ltam8gb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:article-search" /></template>
