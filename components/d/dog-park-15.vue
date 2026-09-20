<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9a8azbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z9a8azbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:dog-park-15" /></template>
