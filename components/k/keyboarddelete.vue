<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rders717g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":641};
const content = `<path class="rders717g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:keyboarddelete" /></template>
