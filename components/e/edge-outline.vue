<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4uaajmnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h4uaajmnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:edge-outline" /></template>
