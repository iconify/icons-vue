<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amc22hb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amc22hb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-left-solid" /></template>
