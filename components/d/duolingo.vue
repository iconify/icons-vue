<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew48wybwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew48wybwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:duolingo" /></template>
