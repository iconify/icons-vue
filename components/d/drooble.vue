<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er3j_9bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er3j_9bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:drooble" /></template>
