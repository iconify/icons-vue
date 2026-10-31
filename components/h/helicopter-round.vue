<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-5n-cbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-5n-cbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:helicopter-round" /></template>
