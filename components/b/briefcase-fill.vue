<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjdk0bbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjdk0bbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:briefcase-fill" /></template>
