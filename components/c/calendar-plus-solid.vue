<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztliwnwek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztliwnwek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:calendar-plus-solid" /></template>
