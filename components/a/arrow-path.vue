<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxss0fhja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxss0fhja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-path" /></template>
