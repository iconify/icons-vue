<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg2v1jbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg2v1jbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:croissant" /></template>
