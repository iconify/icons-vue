<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9-f93mzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9-f93mzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-queen-filled" /></template>
