<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8s1c9zwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8s1c9zwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-baseball-outline" /></template>
