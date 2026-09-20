<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_6o5-b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_6o5-b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-left-right" /></template>
