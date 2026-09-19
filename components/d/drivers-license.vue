<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl-ou4joe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fl-ou4joe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:drivers-license" /></template>
