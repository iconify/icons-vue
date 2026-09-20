<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni-aavqyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni-aavqyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-1-1-filled" /></template>
