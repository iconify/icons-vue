<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gosuq-bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gosuq-bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:circle-half-solid" /></template>
