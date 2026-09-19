<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd_x95izh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="cd_x95izh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:intersectshape" /></template>
