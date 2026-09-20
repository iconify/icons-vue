<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg7k6vike.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bg7k6vike"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-with-vertical-bar" /></template>
