<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrs3rsb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wrs3rsb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-infinite-loop" /></template>
