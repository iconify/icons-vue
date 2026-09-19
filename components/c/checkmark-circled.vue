<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs6xwiblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vs6xwiblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:checkmark-circled" /></template>
