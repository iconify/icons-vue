<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml-ijac5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ml-ijac5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:link-external-fill" /></template>
