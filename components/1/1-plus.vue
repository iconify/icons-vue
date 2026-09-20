<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqznt3_qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hqznt3_qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:1-plus" /></template>
