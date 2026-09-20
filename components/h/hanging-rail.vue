<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn3_w6buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xn3_w6buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hanging-rail" /></template>
