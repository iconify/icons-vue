<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y243fzwzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y243fzwzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dflow-dark" /></template>
