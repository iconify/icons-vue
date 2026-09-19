<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p142kmbwe.css';
import '../../css/x/xo3mlcr-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p142kmbwe"/><path class="xo3mlcr-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-browsers" /></template>
