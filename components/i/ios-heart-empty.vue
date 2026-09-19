<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j438kfbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j438kfbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-heart-empty" /></template>
