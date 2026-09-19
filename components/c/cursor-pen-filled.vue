<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvv9i4bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvv9i4bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-pen-filled" /></template>
