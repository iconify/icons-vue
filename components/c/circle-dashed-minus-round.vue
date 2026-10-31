<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cym504bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cym504bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-minus-round" /></template>
