<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/git3lrbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="git3lrbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha-g-circle-outline" /></template>
