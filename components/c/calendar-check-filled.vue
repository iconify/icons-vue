<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh6xjib1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh6xjib1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-check-filled" /></template>
