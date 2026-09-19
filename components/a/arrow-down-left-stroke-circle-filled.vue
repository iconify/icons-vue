<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3qi18b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3qi18b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-left-stroke-circle-filled" /></template>
