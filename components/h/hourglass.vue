<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6g6t1bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e6g6t1bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hourglass" /></template>
