<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf3d79iqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yf3d79iqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cooked-rice" /></template>
