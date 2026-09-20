<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taug84bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taug84bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-left" /></template>
