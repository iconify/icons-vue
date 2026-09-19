<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5vf289bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5vf289bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-help-empty" /></template>
