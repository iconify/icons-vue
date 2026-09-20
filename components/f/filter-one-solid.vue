<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atlk9tbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atlk9tbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:filter-one-solid" /></template>
