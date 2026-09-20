<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1h-5kbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1h-5kbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:linkedin" /></template>
