<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8b7rebts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j8b7rebts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:basketball-in-basketball-net" /></template>
