<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg35tlbum.css';
import '../../css/a/at_92mbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yg35tlbum"/><path class="at_92mbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-close-outline" /></template>
