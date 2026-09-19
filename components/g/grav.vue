<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc-rd5b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tc-rd5b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:grav" /></template>
