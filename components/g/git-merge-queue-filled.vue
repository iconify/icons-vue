<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnpodroni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnpodroni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-merge-queue-filled" /></template>
