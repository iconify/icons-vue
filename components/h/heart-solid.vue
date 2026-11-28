<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj2wag31f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj2wag31f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heart-solid" /></template>
