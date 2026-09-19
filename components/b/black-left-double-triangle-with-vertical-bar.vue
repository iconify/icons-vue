<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wldnpcbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wldnpcbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:black-left-double-triangle-with-vertical-bar" /></template>
