<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qua-qqbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qua-qqbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chevrons-left" /></template>
