<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqdmvqngq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqdmvqngq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cc" /></template>
