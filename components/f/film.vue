<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ves20yexk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ves20yexk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:film" /></template>
