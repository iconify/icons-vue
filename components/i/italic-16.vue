<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqn8-vbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tqn8-vbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:italic-16" /></template>
