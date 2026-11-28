<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggcg5cysm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggcg5cysm primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ease-linear-duotone" /></template>
