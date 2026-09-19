<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we_-wp3rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="we_-wp3rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bilibili" /></template>
