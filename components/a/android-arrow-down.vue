<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjs1qqrvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjs1qqrvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-arrow-down" /></template>
