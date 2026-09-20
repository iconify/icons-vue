<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhuj0nbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dhuj0nbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-down-small-outline" /></template>
