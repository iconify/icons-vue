<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1693cbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v1693cbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:arpupdown" /></template>
