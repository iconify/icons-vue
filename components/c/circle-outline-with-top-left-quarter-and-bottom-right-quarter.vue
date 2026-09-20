<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn1pn-dlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bn1pn-dlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-outline-with-top-left-quarter-and-bottom-right-quarter" /></template>
