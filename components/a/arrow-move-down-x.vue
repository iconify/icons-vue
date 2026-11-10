<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrlsc76an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrlsc76an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-move-down-x" /></template>
