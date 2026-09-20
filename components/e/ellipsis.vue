<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/recg9ee4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="recg9ee4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:ellipsis" /></template>
