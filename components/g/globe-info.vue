<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsvw7m6as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsvw7m6as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:globe-info" /></template>
