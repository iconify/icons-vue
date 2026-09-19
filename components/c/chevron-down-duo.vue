<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9vamwuzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9vamwuzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-down-duo" /></template>
