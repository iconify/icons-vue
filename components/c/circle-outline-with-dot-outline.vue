<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g02lxkxig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g02lxkxig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-outline-with-dot-outline" /></template>
