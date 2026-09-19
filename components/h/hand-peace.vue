<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7rpd4bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t7rpd4bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hand-peace" /></template>
