<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcn5yl7de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":780,"height":621};
const content = `<path class="vcn5yl7de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:college" /></template>
