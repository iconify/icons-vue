<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt3z6yb7q.css';
import '../../css/m/m635pzbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bt3z6yb7q"/><path class="m635pzbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-stopwatch-outline" /></template>
