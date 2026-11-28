<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm9y-eble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm9y-eble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:loader" /></template>
