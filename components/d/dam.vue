<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtm3f6bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wtm3f6bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:dam" /></template>
