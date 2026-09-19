<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmhkqlb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xmhkqlb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hourglass" /></template>
