<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpnd-hvwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpnd-hvwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-down-outline" /></template>
