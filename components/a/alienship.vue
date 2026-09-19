<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-5w_6mjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="z-5w_6mjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alienship" /></template>
