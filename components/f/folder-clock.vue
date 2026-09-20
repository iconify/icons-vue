<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4rcmbboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4rcmbboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-clock" /></template>
