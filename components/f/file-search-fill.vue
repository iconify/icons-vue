<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oje5wac4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oje5wac4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-search-fill" /></template>
