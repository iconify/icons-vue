<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hklz-72lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hklz-72lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:briefcase-filled" /></template>
