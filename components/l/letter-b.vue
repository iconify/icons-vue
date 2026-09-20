<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekc2a9bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekc2a9bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-b" /></template>
