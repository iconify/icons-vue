<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c276uqo9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c276uqo9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-search-outline" /></template>
