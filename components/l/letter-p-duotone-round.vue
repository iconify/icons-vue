<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvchrvvko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvchrvvko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-p-duotone-round" /></template>
