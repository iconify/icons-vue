<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck9j7l_ys.css';
import '../../css/y/yu7vi3bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ck9j7l_ys"/><path class="yu7vi3bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-thunderstorm-outline" /></template>
