<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlfqkwbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xlfqkwbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-three-small" /></template>
