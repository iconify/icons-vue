<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_6x5wbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_6x5wbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-round" /></template>
