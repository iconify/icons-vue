<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv595n8kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv595n8kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-tree" /></template>
