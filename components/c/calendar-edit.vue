<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsrdic-vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsrdic-vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar-edit" /></template>
