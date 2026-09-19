<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvt193c8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wvt193c8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrows-spin" /></template>
