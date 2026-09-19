<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd01kcbfz.css';
import '../../css/n/nzce9ndyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cd01kcbfz"/><path class="nzce9ndyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pause-outline" /></template>
