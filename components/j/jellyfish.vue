<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq8aiyb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq8aiyb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:jellyfish" /></template>
