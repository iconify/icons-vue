<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z504-5p1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z504-5p1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bus" /></template>
