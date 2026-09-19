<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iai6adbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iai6adbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevrons-left" /></template>
