<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzblnmbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzblnmbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:circle-dashed-check" /></template>
