<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g45duuzpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g45duuzpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:close-square" /></template>
