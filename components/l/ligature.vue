<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-181c0-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j-181c0-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ligature" /></template>
