<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oza3qgbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oza3qgbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-cross-bold" /></template>
