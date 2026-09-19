<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz2sgybcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iz2sgybcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-desktop" /></template>
