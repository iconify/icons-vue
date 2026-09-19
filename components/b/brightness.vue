<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbnr73vgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mbnr73vgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brightness" /></template>
