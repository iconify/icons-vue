<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jofnmtrzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1568};
const content = `<path class="jofnmtrzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bug" /></template>
