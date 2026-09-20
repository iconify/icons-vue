<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjesh0-du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gjesh0-du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:arrow-next-rtl" /></template>
