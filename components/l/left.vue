<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdpaesb5u.css';
import '../../css/r/rr_70iyii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qdpaesb5u"/><path class="rr_70iyii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:left" /></template>
