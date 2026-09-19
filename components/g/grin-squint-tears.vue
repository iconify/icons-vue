<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdaqj9bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cdaqj9bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-squint-tears" /></template>
