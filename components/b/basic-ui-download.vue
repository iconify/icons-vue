<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdhdnennk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hdhdnennk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-download" /></template>
