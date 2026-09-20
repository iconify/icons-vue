<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8f6orbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l8f6orbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cape-landform" /></template>
