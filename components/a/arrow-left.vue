<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia4xzzwuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia4xzzwuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left" /></template>
