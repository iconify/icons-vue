<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgk9ozbah.css';
import '../../css/k/k79q3xboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vgk9ozbah"/><circle class="k79q3xboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-layout-basic" /></template>
