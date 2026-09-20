<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkooc2l-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hkooc2l-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-down-left-16" /></template>
