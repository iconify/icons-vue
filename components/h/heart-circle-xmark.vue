<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkj786brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jkj786brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:heart-circle-xmark" /></template>
