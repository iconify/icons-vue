<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il5s5zklx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="il5s5zklx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-gabled-shelter" /></template>
