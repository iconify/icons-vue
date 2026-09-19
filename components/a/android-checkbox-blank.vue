<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmccvoyjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmccvoyjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-checkbox-blank" /></template>
