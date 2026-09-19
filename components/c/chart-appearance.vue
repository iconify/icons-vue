<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apqxuwf4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apqxuwf4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-appearance" /></template>
