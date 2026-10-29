<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exjkiwm5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exjkiwm5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-search-solid" /></template>
