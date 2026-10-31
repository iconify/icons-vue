<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuqxytbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqxytbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cube-gloss" /></template>
