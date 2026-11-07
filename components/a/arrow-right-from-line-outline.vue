<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly14d-arz.css';
import '../../css/e/exasy4ryo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly14d-arz"/><path class="exasy4ryo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-from-line-outline" /></template>
