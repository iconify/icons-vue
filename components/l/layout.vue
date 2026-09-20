<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3d1abd2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3d1abd2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout" /></template>
