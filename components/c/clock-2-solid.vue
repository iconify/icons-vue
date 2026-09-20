<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u27cibcer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u27cibcer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-2-solid" /></template>
