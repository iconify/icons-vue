<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m069-ebdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m069-ebdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-circle" /></template>
