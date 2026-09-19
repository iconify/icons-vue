<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb2unwdfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mb2unwdfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-paper" /></template>
