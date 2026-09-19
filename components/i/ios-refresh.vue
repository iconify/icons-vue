<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nko9w9bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nko9w9bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-refresh" /></template>
