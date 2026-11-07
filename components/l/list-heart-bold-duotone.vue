<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ophijtbsv.css';
import '../../css/s/samvw5boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ophijtbsv"/><path class="samvw5boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-heart-bold-duotone" /></template>
