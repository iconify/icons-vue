<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwa9eacvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dwa9eacvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowshape-turn-up-left-circle" /></template>
