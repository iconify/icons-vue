<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1ich61cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ich61cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:group-fill-round" /></template>
