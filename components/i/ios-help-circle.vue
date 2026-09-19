<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3-g7fbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b3-g7fbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-help-circle" /></template>
