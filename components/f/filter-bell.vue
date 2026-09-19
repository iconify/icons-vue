<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jasz3fyxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jasz3fyxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-bell" /></template>
