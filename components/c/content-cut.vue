<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zh5ebzg.css';
import '../../css/c/ctmkibhti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x6zh5ebzg"/><path class="ctmkibhti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-cut" /></template>
