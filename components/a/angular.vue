<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtnxyp9na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jtnxyp9na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:angular" /></template>
