<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnz27eb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hnz27eb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-git-branch" /></template>
