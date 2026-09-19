<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k810wbbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k810wbbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-s-left-filled" /></template>
