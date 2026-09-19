<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfg8bo1tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="cfg8bo1tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alignjustify" /></template>
