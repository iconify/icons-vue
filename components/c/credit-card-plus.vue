<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug3rzl7ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug3rzl7ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:credit-card-plus" /></template>
