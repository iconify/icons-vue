<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at64shbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="at64shbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:hourglass" /></template>
