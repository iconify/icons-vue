<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s247otyll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s247otyll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-search-outline" /></template>
