<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7vmeuosh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="s7vmeuosh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-right" /></template>
