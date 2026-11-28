<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvyuokbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nvyuokbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:letter-spacing-fill" /></template>
