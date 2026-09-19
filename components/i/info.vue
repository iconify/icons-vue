<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeurl0igg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xeurl0igg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:info" /></template>
