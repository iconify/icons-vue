<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt8m-8zdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt8m-8zdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-top-line" /></template>
