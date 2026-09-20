<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9peebclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h9peebclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:buoy" /></template>
