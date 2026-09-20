<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6liw8z9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6liw8z9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:link" /></template>
