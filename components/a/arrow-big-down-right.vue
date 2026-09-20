<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y029h9jjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y029h9jjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-big-down-right" /></template>
