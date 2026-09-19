<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljm7f5bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ljm7f5bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-top-left-center-8" /></template>
