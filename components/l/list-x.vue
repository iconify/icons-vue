<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0ocnnfze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0ocnnfze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-x" /></template>
