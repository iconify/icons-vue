<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8rq7tskk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8rq7tskk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bolivia" /></template>
