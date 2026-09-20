<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oex_pe6-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oex_pe6-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:format-strikethrough-16" /></template>
