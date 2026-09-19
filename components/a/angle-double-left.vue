<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mro34mbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":992,"height":1280};
const content = `<path class="mro34mbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:angle-double-left" /></template>
