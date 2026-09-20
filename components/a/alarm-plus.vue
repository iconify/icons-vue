<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo-uomb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo-uomb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-plus" /></template>
