<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flqsglbac.css';
import '../../css/l/l_r5ns7jv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="flqsglbac"/><path class="l_r5ns7jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-swap" /></template>
