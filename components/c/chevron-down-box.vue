<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eym5mrbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eym5mrbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-down-box" /></template>
