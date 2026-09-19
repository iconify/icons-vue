<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5x-7fbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5x-7fbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-right-left" /></template>
