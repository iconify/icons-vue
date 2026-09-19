<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap8rfcbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ap8rfcbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:cross" /></template>
