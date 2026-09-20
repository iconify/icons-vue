<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofufdvmay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofufdvmay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-6-fill" /></template>
