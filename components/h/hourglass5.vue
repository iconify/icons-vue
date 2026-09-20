<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh53vfb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eh53vfb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass5" /></template>
