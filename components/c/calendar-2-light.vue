<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwvcop_jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwvcop_jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-2-light" /></template>
