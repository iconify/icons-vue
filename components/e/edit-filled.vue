<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5xymnzul.css';
import '../../css/y/y1nb_hosg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5xymnzul"/><path class="y1nb_hosg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:edit-filled" /></template>
