<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqe6wgboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqe6wgboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-up-circle-filled" /></template>
