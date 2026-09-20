<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zracorrhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zracorrhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:crowd-of-people" /></template>
