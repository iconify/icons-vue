<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f012s1pie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f012s1pie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-with-canoe" /></template>
