<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx416jb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vx416jb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:clock" /></template>
