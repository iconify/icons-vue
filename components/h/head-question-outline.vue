<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbhx-705c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbhx-705c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-question-outline" /></template>
