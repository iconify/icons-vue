<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9d9kacnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9d9kacnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-sharp-fill" /></template>
