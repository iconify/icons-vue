<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4_b4bczb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4_b4bczb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-left-stroke-circle-filled" /></template>
