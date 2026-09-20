<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krhed0bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krhed0bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-multiple-outline" /></template>
