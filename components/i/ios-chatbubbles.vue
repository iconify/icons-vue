<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioyychypw.css';
import '../../css/a/ahrqr1byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ioyychypw"/><path class="ahrqr1byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-chatbubbles" /></template>
