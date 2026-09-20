<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2yd9po6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2yd9po6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:grid-one" /></template>
