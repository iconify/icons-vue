<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq-4ibcwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq-4ibcwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-stroke" /></template>
