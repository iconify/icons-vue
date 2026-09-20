<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0d5y6b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h0d5y6b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-up-bold" /></template>
