<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbfz-wywq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qbfz-wywq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-git-merge" /></template>
