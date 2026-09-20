<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4gcr8b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4gcr8b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hostinger" /></template>
