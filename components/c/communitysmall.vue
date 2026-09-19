<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f87xs6bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f87xs6bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:communitysmall" /></template>
