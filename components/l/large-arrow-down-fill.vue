<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t--3ic8dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t--3ic8dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-down-fill" /></template>
