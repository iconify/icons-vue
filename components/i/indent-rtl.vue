<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa4glgq1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aa4glgq1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:indent-rtl" /></template>
