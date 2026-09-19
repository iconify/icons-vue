<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9sar8ywe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9sar8ywe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:code" /></template>
