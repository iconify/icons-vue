<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui_yqjhja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ui_yqjhja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:left-magnifying-glass" /></template>
