<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i395cqb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i395cqb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ibm" /></template>
