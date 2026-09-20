<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpful-bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpful-bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:greek-cross-above-outstretched-hand" /></template>
