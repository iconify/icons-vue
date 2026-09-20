<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y42wgcbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y42wgcbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-right-to-right-bracket" /></template>
