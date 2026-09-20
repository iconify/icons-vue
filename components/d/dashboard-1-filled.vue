<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tckw8clyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tckw8clyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dashboard-1-filled" /></template>
