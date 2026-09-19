<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiw2f8g6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qiw2f8g6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:cone" /></template>
