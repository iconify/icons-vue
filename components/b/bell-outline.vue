<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9l-53e4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a9l-53e4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bell-outline" /></template>
