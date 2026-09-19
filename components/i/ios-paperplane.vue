<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhvnz9bwg.css';
import '../../css/s/soter0kom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hhvnz9bwg"/><path class="soter0kom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-paperplane" /></template>
