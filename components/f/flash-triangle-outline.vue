<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvlp93b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvlp93b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flash-triangle-outline" /></template>
