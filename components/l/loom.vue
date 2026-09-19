<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unumhvbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b unumhvbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:loom" /></template>
