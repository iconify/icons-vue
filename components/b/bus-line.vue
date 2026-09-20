<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g51j71bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g51j71bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bus-line" /></template>
