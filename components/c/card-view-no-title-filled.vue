<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxfy42b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="yxfy42b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:card-view-no-title-filled" /></template>
