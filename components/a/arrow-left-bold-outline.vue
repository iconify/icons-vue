<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxtnnqb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxtnnqb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bold-outline" /></template>
