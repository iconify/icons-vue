<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4yav7kxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4yav7kxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-left-stroke" /></template>
