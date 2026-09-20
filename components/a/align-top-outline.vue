<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8c63piap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8c63piap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-top-outline" /></template>
