<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8l04ubve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8l04ubve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:background-base-fill" /></template>
