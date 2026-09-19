<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqgm7gb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":562,"height":768};
const content = `<path class="yqgm7gb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:d" /></template>
