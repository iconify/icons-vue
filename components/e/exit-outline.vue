<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxw75molp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jxw75molp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:exit-outline" /></template>
